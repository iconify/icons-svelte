<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubhv2wblo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubhv2wblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:music-2-filled" {...props}></Icon>
