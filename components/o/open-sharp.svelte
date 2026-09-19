<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5surlbgg.css';
import '../../css/s/stpx8h04v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5surlbgg"/><path class="stpx8h04v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:open-sharp" {...props}></Icon>
