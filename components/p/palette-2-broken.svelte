<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l9pb4jh3n.css';
import '../../css/y/yzxt5rhfr.css';
import '../../css/y/yi78wl5tr.css';
import '../../css/c/c3hdb9bdc.css';
import '../../css/z/zlbyb8b6o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l9pb4jh3n"/><circle class="yzxt5rhfr"/><circle class="yi78wl5tr"/><path class="c3hdb9bdc"/><path class="zlbyb8b6o"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:palette-2-broken" {...props}></Icon>
