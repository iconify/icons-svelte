<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnjpk8bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnjpk8bom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:apple-logo-fill-round" {...props}></Icon>
