<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uw_44nilr.css';
import '../../css/v/v9zanyf3o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uw_44nilr"/><path class="v9zanyf3o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:new-tab" {...props}></Icon>
