<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r2qqo_bou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":496};
const content = `<path class="r2qqo_bou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mic-setting" {...props}></Icon>
