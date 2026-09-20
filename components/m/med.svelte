<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lftxn_y7p.css';
import '../../css/c/ct7mdezdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lftxn_y7p"/><path class="ct7mdezdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:med" {...props}></Icon>
