<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf3z-bcyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kf3z-bcyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:checkbox" {...props}></Icon>
