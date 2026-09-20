<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5mh2ibhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e5mh2ibhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:google-photos-logo-solid" {...props}></Icon>
