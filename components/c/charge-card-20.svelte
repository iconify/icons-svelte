<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/abo8mtx2l.css';
import '../../css/r/ra-v9ybun.css';
import '../../css/v/vrssy_bnt.css';
import '../../css/r/rdtqoi99p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="abo8mtx2l"/><path class="ra-v9ybun"/><path class="vrssy_bnt"/><path class="rdtqoi99p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charge-card-20" {...props}></Icon>
