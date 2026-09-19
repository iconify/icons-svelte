<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scpytbcyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="scpytbcyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:circle-notch" {...props}></Icon>
