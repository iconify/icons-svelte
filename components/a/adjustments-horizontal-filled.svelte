<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9kuimbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9kuimbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:adjustments-horizontal-filled" {...props}></Icon>
