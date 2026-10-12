<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1t7v_btd.css';
import '../../css/j/jhru-hx-c.css';
import '../../css/v/vw_n11rmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x1t7v_btd"/><path class="jhru-hx-c"/><path class="vw_n11rmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-lock-20-bold" {...props}></Icon>
