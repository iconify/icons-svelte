<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fw4kgw1nz.css';
import '../../css/s/sd8hp-bgw.css';
import '../../css/i/idx-jsb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fw4kgw1nz"/><path class="sd8hp-bgw"/><path class="idx-jsb0m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:phone-log-duotone" {...props}></Icon>
