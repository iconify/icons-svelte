<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y3fi3cbul.css';
import '../../css/l/l_4g_xmjp.css';
import '../../css/a/adc7zwbbk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y3fi3cbul"/><path class="l_4g_xmjp"/><path class="adc7zwbbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:phone-outgoing-20-bold" {...props}></Icon>
