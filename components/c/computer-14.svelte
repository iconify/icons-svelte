<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufcva7b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="ufcva7b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:computer-14" {...props}></Icon>
