<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrjjpabrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="jrjjpabrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:location-pin-medical-hospital-2-solid" {...props}></Icon>
