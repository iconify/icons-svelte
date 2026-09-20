<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s0sl8tbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s0sl8tbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:credit-card-multiple" {...props}></Icon>
