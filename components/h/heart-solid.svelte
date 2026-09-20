<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3teuyc5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t3teuyc5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:heart-solid" {...props}></Icon>
