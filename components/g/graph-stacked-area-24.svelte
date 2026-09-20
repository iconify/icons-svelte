<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsyatab4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsyatab4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:graph-stacked-area-24" {...props}></Icon>
