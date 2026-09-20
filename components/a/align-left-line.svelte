<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y-wtz1env.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y-wtz1env"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-left-line" {...props}></Icon>
