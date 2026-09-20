<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ahzi-5k8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ahzi-5k8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:invoice-text-fast" {...props}></Icon>
