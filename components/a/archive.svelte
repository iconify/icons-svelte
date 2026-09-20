<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8q8o-yoi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a8q8o-yoi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:archive" {...props}></Icon>
