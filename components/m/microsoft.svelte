<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fes7web_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fes7web_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:microsoft" {...props}></Icon>
