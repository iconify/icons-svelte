<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b5k6uosue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b5k6uosue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:download-twice-square-bold" {...props}></Icon>
