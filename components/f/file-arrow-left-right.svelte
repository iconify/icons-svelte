<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx1cgxh8m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx1cgxh8m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-arrow-left-right" {...props}></Icon>
