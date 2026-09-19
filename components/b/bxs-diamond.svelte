<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc8a5iqwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc8a5iqwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-diamond" {...props}></Icon>
