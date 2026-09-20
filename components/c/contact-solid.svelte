<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hkc4x7rmc.css';
import '../../css/j/j5ymz25ec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="hkc4x7rmc"/><path class="j5ymz25ec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:contact-solid" {...props}></Icon>
