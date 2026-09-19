<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygif-0zjx.css';
import '../../css/v/v5gp01b5h.css';
import '../../css/l/l4t-_sbed.css';
import '../../css/g/gtb-nw37z.css';
import '../../css/u/uq8obbc2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ygif-0zjx"/><ellipse class="v5gp01b5h"/><ellipse class="l4t-_sbed"/><ellipse class="gtb-nw37z"/><ellipse class="uq8obbc2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:paw-sharp" {...props}></Icon>
