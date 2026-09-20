<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ka56i2i7o.css';
import '../../css/p/ppaop13hw.css';
import '../../css/f/f0-nx3ual.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":584.485};
const content = `<path class="ka56i2i7o"/><path class="ppaop13hw"/><path class="f0-nx3ual"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:best-buy" {...props}></Icon>
