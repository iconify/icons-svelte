<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3rsx1buz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="c3rsx1buz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:hand-back-fist" {...props}></Icon>
