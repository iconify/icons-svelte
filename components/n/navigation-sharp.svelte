<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v47hdr-ij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v47hdr-ij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:navigation-sharp" {...props}></Icon>
