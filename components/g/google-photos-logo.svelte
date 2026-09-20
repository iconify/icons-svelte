<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjc6glbvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjc6glbvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-photos-logo" {...props}></Icon>
