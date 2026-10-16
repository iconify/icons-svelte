<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/diwypubsb.css';
import '../../css/y/yw1m5wbef.css';
import '../../css/z/zpuo1ebll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="diwypubsb"/><path class="yw1m5wbef"/><path class="zpuo1ebll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:currency-exchange-20" {...props}></Icon>
