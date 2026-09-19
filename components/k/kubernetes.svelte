<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wt53_51gy.css';
import '../../css/j/jvxlq78ce.css';
import '../../css/j/j_vpq2bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wt53_51gy"/><path class="jvxlq78ce"/><path class="j_vpq2bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:kubernetes" {...props}></Icon>
