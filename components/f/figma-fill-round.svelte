<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfv8xnp-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfv8xnp-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:figma-fill-round" {...props}></Icon>
