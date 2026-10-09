<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fx8d4-q2n.css';
import '../../css/f/fjtwhsb_o.css';
import '../../css/p/pxpj-8byp.css';
import '../../css/u/u8yg584ct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fx8d4-q2n"/><path class="fjtwhsb_o"/><path class="pxpj-8byp"/><path class="u8yg584ct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:construction-crane-48" {...props}></Icon>
