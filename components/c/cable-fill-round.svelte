<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0q9ekbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u0q9ekbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:cable-fill-round" {...props}></Icon>
