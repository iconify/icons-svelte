<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-be4tb1z.css';
import '../../css/f/fijx44bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l-be4tb1z wm-k"/><path class="fijx44bhr wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:arrow-down-right" {...props}></Icon>
