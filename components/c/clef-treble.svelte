<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ziwy33b3c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ziwy33b3c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:clef-treble" {...props}></Icon>
