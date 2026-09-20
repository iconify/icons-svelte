<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oixz44knh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="oixz44knh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:place-of-worship-14" {...props}></Icon>
