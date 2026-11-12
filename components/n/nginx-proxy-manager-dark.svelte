<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv-0_mbqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cv-0_mbqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nginx-proxy-manager-dark" {...props}></Icon>
