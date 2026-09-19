<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xm-rn_6_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xm-rn_6_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:bug" {...props}></Icon>
