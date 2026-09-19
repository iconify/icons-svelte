<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtksr2b6j.css';
import '../../css/j/j4-0chb9k.css';
import '../../css/r/ratngrhrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="xtksr2b6j"/><path class="j4-0chb9k"/><path class="ratngrhrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:photograph" {...props}></Icon>
