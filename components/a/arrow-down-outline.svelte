<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mxvf2cbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="mxvf2cbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:arrow-down-outline" {...props}></Icon>
