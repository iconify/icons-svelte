<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z051ocbir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z051ocbir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nexxt" {...props}></Icon>
