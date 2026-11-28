<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3s7s_b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3s7s_b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:play" {...props}></Icon>
