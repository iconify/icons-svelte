<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l33upq_ln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l33upq_ln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:knife-line" {...props}></Icon>
