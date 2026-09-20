<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fhd73iz3o.css';
import '../../css/f/fjk7q33ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fhd73iz3o"/><path class="fjk7q33ni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:heyform-dark" {...props}></Icon>
