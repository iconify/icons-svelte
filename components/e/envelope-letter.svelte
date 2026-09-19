<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iky9k_b7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iky9k_b7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:envelope-letter" {...props}></Icon>
