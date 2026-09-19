<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ciq5eq_zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ciq5eq_zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:circle-fading-plus" {...props}></Icon>
