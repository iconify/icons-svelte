<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dtrm-5ano.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dtrm-5ano"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:add-invoice" {...props}></Icon>
