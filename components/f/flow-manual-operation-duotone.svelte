<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnv7t_j2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cnv7t_j2w primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:flow-manual-operation-duotone" {...props}></Icon>
