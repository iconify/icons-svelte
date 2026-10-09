<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsr_drbgn.css';
import '../../css/p/pfaueebia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fsr_drbgn"/><path class="pfaueebia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:edit-20-bold" {...props}></Icon>
