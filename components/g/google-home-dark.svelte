<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjgsc_5dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kjgsc_5dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-home-dark" {...props}></Icon>
