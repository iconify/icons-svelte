<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfrw229ma.css';
import '../../css/y/yz4sh9bvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bfrw229ma"/><path class="yz4sh9bvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-photos" {...props}></Icon>
