<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mth0oeb6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mth0oeb6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:data-file-graph-bold" {...props}></Icon>
