<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txum_rt2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txum_rt2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:clipboard-text-multiple" {...props}></Icon>
