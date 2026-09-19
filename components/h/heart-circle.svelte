<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_vii1mtq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_vii1mtq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:heart-circle" {...props}></Icon>
