<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lprujtblw.css';
import '../../css/m/mti94ib8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lprujtblw"/><path class="mti94ib8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:border-outer" {...props}></Icon>
