<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuzrn2ucu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xuzrn2ucu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:loudly-crying-face" {...props}></Icon>
