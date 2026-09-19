<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arb42vspr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="arb42vspr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:location" {...props}></Icon>
