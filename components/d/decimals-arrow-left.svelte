<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u19-v4beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u19-v4beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:decimals-arrow-left" {...props}></Icon>
