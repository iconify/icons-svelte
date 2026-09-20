<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwuo_rm-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bwuo_rm-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:altcha" {...props}></Icon>
