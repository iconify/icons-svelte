<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dn71nbsre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dn71nbsre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:printer-cloud-line" {...props}></Icon>
