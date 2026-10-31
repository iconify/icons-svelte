<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq34xl16r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq34xl16r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:bone-round" {...props}></Icon>
