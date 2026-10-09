<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gkt9q_b2i.css';
import '../../css/p/pczwsit1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gkt9q_b2i"/><path class="pczwsit1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:laundry-basket-48" {...props}></Icon>
