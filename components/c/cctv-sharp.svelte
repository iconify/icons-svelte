<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhdk_e98b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhdk_e98b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:cctv-sharp" {...props}></Icon>
