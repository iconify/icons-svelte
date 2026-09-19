<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxg60abnf.css';
import '../../css/o/oajkybcsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sxg60abnf"/><path class="oajkybcsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:mod" {...props}></Icon>
