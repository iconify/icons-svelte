<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjvd0-bgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vjvd0-bgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:qr-code-search" {...props}></Icon>
