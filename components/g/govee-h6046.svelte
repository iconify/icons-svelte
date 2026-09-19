<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvcc9_byb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvcc9_byb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:govee-h6046" {...props}></Icon>
