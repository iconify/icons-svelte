<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tyr_tub4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tyr_tub4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:ev-charger" {...props}></Icon>
