<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e6glm1bic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e6glm1bic"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cycling-74" {...props}></Icon>
