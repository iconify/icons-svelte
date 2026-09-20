<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeizw41cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeizw41cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:church-line" {...props}></Icon>
