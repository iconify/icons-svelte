<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q80nobcae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q80nobcae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:broadcast" {...props}></Icon>
