<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqv-4hvik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vqv-4hvik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:gas-pump" {...props}></Icon>
