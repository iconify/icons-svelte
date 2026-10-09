<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcjkvkwqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lcjkvkwqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:i-beam-48-bold" {...props}></Icon>
