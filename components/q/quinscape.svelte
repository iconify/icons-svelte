<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npv1kvbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="npv1kvbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:quinscape" {...props}></Icon>
