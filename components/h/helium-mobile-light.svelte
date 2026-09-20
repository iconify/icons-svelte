<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq9f5tbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hq9f5tbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:helium-mobile-light" {...props}></Icon>
