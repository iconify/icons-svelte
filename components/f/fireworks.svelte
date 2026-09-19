<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euyzp-gep.css';
import '../../css/n/n0_pd6b2y.css';
import '../../css/i/it6f6naqc.css';
import '../../css/v/vjkf9voyj.css';
import '../../css/c/c-fcwn0fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="euyzp-gep"/><path class="n0_pd6b2y"/><path class="it6f6naqc"/><path class="vjkf9voyj"/><path class="c-fcwn0fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:fireworks" {...props}></Icon>
