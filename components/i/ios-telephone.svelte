<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nsfcpabqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nsfcpabqs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-telephone" {...props}></Icon>
