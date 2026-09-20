<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_489zzen.css';
import '../../css/i/ibxo5zbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="c_489zzen"/><path class="ibxo5zbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:raised-hand-dark-skin-tone" {...props}></Icon>
