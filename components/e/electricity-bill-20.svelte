<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pepcxkbtl.css';
import '../../css/b/bkagalxid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pepcxkbtl"/><path class="bkagalxid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electricity-bill-20" {...props}></Icon>
