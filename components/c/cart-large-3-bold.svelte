<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/o/oioeggbqi.css';
import '../../css/n/nwt30bbwd.css';
import '../../css/w/wq4mdib6y.css';
import '../../css/m/m18bd8w-e.css';
import '../../css/v/vshvrf3tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="oioeggbqi"/><path class="nwt30bbwd"/><path class="wq4mdib6y"/><path class="m18bd8w-e"/><path class="vshvrf3tz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cart-large-3-bold" {...props}></Icon>
