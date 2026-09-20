<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/no6vjtbbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="no6vjtbbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:home-assistant-matter-hub-dark" {...props}></Icon>
