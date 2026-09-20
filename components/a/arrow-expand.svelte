<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqe-16brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="nqe-16brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:arrow-expand" {...props}></Icon>
