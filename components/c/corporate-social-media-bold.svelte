<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq8wm8bub.css';
import '../../css/m/mryp9vb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq8wm8bub"/><path class="mryp9vb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:corporate-social-media-bold" {...props}></Icon>
