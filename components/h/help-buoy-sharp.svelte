<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3yvj_ezw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k3yvj_ezw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:help-buoy-sharp" {...props}></Icon>
