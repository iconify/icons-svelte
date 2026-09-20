<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv4va0_8o.css';
import '../../css/l/lf01q5b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4va0_8o"/><path class="lf01q5b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:aiming-line" {...props}></Icon>
