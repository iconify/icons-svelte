<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2qefrbah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2qefrbah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:align-horizontal-center" {...props}></Icon>
