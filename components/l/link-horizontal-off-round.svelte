<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v2-n-e3ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v2-n-e3ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:link-horizontal-off-round" {...props}></Icon>
