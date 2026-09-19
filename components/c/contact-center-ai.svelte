<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-vmlkb_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-vmlkb_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:contact-center-ai" {...props}></Icon>
