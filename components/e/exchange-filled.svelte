<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/urn-slpun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="urn-slpun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:exchange-filled" {...props}></Icon>
