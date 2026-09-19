<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omu70acdu.css';
import '../../css/x/x_6zwgo6p.css';
import '../../css/v/v23eax-8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="omu70acdu"/><path class="x_6zwgo6p"/><path class="v23eax-8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:ladybeetle" {...props}></Icon>
