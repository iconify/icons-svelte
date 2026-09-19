<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzjp_-b9c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzjp_-b9c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:mode-dark" {...props}></Icon>
