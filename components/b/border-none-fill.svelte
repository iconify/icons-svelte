<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mc4u2xbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="mc4u2xbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:border-none-fill" {...props}></Icon>
