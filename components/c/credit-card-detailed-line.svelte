<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvfunrbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vvfunrbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:credit-card-detailed-line" {...props}></Icon>
