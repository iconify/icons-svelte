<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdl6qwbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdl6qwbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:bed" {...props}></Icon>
