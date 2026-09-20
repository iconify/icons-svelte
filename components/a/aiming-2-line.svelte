<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1ucmp_vc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j1ucmp_vc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aiming-2-line" {...props}></Icon>
