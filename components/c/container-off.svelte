<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ao7ij_ccs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ao7ij_ccs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:container-off" {...props}></Icon>
