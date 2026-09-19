<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mld48g7cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mld48g7cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:parallel-filled" {...props}></Icon>
