<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km69o8ksh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="km69o8ksh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:folder-open-outline" {...props}></Icon>
