<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf5e126wj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xf5e126wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fritz-light" {...props}></Icon>
