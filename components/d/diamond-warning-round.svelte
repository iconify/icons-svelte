<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nmbeninbc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nmbeninbc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:diamond-warning-round" {...props}></Icon>
