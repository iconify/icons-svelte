<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkb-y5lvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lkb-y5lvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:arrow-down-left-box-outline" {...props}></Icon>
