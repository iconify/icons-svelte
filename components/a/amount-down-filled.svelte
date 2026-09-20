<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r9qkdc_cf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r9qkdc_cf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:amount-down-filled" {...props}></Icon>
