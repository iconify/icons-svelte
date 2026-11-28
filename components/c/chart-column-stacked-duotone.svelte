<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evq3bovfu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evq3bovfu primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:chart-column-stacked-duotone" {...props}></Icon>
