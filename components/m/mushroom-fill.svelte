<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_42t67jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_42t67jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mushroom-fill" {...props}></Icon>
