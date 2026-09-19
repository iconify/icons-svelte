<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx3tnd3zx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx3tnd3zx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:anthos-service-mesh" {...props}></Icon>
