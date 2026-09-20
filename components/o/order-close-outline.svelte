<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_mclbccr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="o_mclbccr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:order-close-outline" {...props}></Icon>
