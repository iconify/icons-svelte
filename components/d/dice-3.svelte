<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd4_1pb7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vd4_1pb7p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:dice-3" {...props}></Icon>
