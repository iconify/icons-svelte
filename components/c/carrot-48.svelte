<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2l2_ebga.css';
import '../../css/g/gjxcd2b_y.css';
import '../../css/e/ebxyc5bix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i2l2_ebga"/><path class="gjxcd2b_y"/><path class="ebxyc5bix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:carrot-48" {...props}></Icon>
