<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xff7nngrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xff7nngrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:case-upper" {...props}></Icon>
