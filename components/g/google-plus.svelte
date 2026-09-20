<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/edo_wmwla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="edo_wmwla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:google-plus" {...props}></Icon>
