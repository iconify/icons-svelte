<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv3lw8b4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sv3lw8b4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:blockbench" {...props}></Icon>
