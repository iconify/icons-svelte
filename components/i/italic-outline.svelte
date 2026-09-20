<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dll7k3y3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dll7k3y3y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:italic-outline" {...props}></Icon>
