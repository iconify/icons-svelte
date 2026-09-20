<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c11lxbcko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c11lxbcko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:grid-circles-duotone" {...props}></Icon>
