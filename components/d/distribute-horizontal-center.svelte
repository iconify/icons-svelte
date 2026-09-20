<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqhuv0_bx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pqhuv0_bx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:distribute-horizontal-center" {...props}></Icon>
