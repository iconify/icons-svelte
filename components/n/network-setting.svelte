<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sn0wjeoky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sn0wjeoky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:network-setting" {...props}></Icon>
