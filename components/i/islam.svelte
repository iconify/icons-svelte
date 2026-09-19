<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veoe9mbus.css';
import '../../css/p/pf8dc_bap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veoe9mbus"/><path class="pf8dc_bap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:islam" {...props}></Icon>
