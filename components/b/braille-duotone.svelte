<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqtv_8b1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary rqtv_8b1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:braille-duotone" {...props}></Icon>
