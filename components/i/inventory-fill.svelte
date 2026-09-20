<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fveusnqss.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fveusnqss"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:inventory-fill" {...props}></Icon>
