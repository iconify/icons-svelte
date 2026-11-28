<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow1t_ubre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow1t_ubre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:projector-x" {...props}></Icon>
