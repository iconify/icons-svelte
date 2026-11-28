<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb-w71_su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary zb-w71_su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:plane-off-duotone" {...props}></Icon>
