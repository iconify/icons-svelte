<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srf3omgjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srf3omgjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:paperclip-2-broken" {...props}></Icon>
