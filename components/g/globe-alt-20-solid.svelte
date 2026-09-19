<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2p5n4w2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m2p5n4w2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:globe-alt-20-solid" {...props}></Icon>
