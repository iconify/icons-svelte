<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wx9kngbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wx9kngbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:figshare-square" {...props}></Icon>
