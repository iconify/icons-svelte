<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohzvlnp0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ohzvlnp0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:progress-50-line" {...props}></Icon>
