<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt2675bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nt2675bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:microphone-outline" {...props}></Icon>
