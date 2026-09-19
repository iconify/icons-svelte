<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pdtxb_m1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pdtxb_m1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:backward-step-fill" {...props}></Icon>
