<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjv5k8bns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="kjv5k8bns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:muslim-14" {...props}></Icon>
