<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl4-mubxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xl4-mubxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:receipt" {...props}></Icon>
