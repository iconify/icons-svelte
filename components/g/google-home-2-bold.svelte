<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2n2hbb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m2n2hbb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:google-home-2-bold" {...props}></Icon>
