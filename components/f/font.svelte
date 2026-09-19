<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oha6hnoud.css';
import '../../css/c/c8_pid-oz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oha6hnoud"/><path class="c8_pid-oz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:font" {...props}></Icon>
