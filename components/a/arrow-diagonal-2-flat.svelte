<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgnaupfol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fgnaupfol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:arrow-diagonal-2-flat" {...props}></Icon>
