<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hv7_8fbub.css';
import '../../css/s/sgaegpv7c.css';
import '../../css/f/fv65liyxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hv7_8fbub"/><path class="sgaegpv7c"/><path class="fv65liyxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-pull-request-20" {...props}></Icon>
