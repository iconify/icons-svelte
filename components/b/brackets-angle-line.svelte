<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/acw94x52i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="acw94x52i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:brackets-angle-line" {...props}></Icon>
