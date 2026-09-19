<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ril1flb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="ril1flb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:circle-fill" {...props}></Icon>
