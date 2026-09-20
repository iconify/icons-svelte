<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_m9638xq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_m9638xq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:medical-cross-circle" {...props}></Icon>
