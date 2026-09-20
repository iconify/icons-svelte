<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwk4867sm.css';
import '../../css/n/n7yph_i7l.css';
import '../../css/q/qr-5js_2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwk4867sm"/><path class="n7yph_i7l"/><path class="qr-5js_2c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-kchat-dark" {...props}></Icon>
