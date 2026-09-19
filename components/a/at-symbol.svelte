<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2622zbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2622zbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="humbleicons:at-symbol" {...props}></Icon>
