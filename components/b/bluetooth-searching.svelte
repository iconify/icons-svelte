<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl6m2oa_c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xl6m2oa_c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:bluetooth-searching" {...props}></Icon>
