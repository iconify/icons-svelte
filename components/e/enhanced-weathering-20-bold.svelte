<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6aotmbvd.css';
import '../../css/w/wc6br1b7o.css';
import '../../css/v/v5azrzqtg.css';
import '../../css/b/bb1dkhbtn.css';
import '../../css/i/i4s3gsb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t6aotmbvd"/><path class="wc6br1b7o"/><path class="v5azrzqtg"/><path class="bb1dkhbtn"/><path class="i4s3gsb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:enhanced-weathering-20-bold" {...props}></Icon>
