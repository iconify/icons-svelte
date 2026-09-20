<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzfci_b_j.css';
import '../../css/u/u3uqfyj5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzfci_b_j"/><path class="u3uqfyj5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:deso" {...props}></Icon>
