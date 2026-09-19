<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_y_-wofq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q_y_-wofq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:chevron-up-circle-sharp" {...props}></Icon>
