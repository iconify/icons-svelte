<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/keov08rnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="keov08rnv primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-right-through-line-duotone" {...props}></Icon>
