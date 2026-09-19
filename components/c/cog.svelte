<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfim0fz_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":740,"height":830};
const content = `<path class="rfim0fz_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:cog" {...props}></Icon>
