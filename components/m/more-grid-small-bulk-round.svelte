<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtvf1bb1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xtvf1bb1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:more-grid-small-bulk-round" {...props}></Icon>
