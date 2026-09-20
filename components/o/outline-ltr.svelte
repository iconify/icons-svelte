<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cod50bpfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cod50bpfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:outline-ltr" {...props}></Icon>
