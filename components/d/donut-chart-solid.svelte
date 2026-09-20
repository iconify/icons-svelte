<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ghei44brf.css';
import '../../css/y/ygr7rgb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ghei44brf"/><path class="ygr7rgb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:donut-chart-solid" {...props}></Icon>
