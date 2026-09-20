<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwhh-p3kj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hwhh-p3kj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cross-fill" {...props}></Icon>
