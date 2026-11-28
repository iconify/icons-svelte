<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f40ypprxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f40ypprxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:robot-vacuum-check" {...props}></Icon>
