<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3fg58wzn.css';
import '../../css/g/g_zluxtrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="u3fg58wzn"/><path class="g_zluxtrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:briefcase-plus-1" {...props}></Icon>
