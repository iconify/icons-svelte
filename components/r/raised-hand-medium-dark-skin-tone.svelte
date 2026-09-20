<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g712a07tq.css';
import '../../css/i/ibxo5zbky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="g712a07tq"/><path class="ibxo5zbky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:raised-hand-medium-dark-skin-tone" {...props}></Icon>
