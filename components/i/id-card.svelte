<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pio0e7bsu.css';
import '../../css/w/wdohmybjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pio0e7bsu"/><path class="wdohmybjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="prime:id-card" {...props}></Icon>
