<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxj-05m9f.css';
import '../../css/w/wafsj8bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="sxj-05m9f"/><path class="wafsj8bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electrolyser-48-bold" {...props}></Icon>
