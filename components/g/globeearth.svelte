<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap-28x_nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<path class="ap-28x_nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wpf:globeearth" {...props}></Icon>
