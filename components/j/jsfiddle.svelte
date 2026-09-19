<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awu1eodbb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="awu1eodbb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:jsfiddle" {...props}></Icon>
