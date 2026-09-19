<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8_pid-oz.css';
import '../../css/d/dbej1sbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c8_pid-oz"/><path class="dbej1sbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:header" {...props}></Icon>
