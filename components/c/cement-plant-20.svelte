<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzr0hm98u.css';
import '../../css/z/zoam-0bdz.css';
import '../../css/f/fl-um2bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zzr0hm98u"/><path class="zoam-0bdz"/><path class="fl-um2bwn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cement-plant-20" {...props}></Icon>
