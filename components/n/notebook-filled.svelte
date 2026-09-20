<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdyjpsboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bdyjpsboi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notebook-filled" {...props}></Icon>
