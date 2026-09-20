<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs-zas9_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs-zas9_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-cloud-light" {...props}></Icon>
