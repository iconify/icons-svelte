<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dw766jryt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dw766jryt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bread-01" {...props}></Icon>
