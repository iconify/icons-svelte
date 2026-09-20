<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwa_0acop.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mwa_0acop"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:calendar" {...props}></Icon>
