<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2ma0q-hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2ma0q-hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:enter-bold" {...props}></Icon>
