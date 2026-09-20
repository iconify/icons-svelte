<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8lpo2d8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n8lpo2d8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:nintendo-switch-outline" {...props}></Icon>
