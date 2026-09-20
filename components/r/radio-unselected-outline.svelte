<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trp_db72c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="trp_db72c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:radio-unselected-outline" {...props}></Icon>
