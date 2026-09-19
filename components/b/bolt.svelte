<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc-tw6bpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mc-tw6bpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:bolt" {...props}></Icon>
