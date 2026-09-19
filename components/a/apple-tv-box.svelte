<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghl62r_kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ghl62r_kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:apple-tv-box" {...props}></Icon>
