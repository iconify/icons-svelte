<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okhxp7bdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="okhxp7bdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:file-ppt-2-fill" {...props}></Icon>
