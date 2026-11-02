<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kd8tv7mwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kd8tv7mwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palette-2-fill" {...props}></Icon>
