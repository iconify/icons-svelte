<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6oa8knwz.css';
import '../../css/x/xxgbczr8p.css';
import '../../css/c/c6b6y2bkd.css';
import '../../css/n/nf_ginl5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n6oa8knwz"/><path class="xxgbczr8p"/><path class="c6b6y2bkd"/><path class="nf_ginl5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:floating-wind-20" {...props}></Icon>
