<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eclf4bb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eclf4bb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:land-plot-line" {...props}></Icon>
