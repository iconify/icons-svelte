<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp6mlgbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="cp6mlgbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pinterest" {...props}></Icon>
