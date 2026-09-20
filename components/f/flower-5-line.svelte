<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du2f62gcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="du2f62gcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-5-line" {...props}></Icon>
