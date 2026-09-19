<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0jxknbfz.css';
import '../../css/j/jmjky1e4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c0jxknbfz"/><path class="jmjky1e4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-registered" {...props}></Icon>
