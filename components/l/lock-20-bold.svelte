<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wlaay_4cm.css';
import '../../css/f/f4g0gcbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wlaay_4cm"/><path class="f4g0gcbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-20-bold" {...props}></Icon>
