<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mw3rfebax.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mw3rfebax"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:cross-small" {...props}></Icon>
