<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp7kmub6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp7kmub6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:key" {...props}></Icon>
