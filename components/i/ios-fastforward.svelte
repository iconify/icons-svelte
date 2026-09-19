<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj_7ijbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hj_7ijbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-fastforward" {...props}></Icon>
