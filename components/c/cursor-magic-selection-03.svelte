<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kn69s8bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn69s8bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cursor-magic-selection-03" {...props}></Icon>
