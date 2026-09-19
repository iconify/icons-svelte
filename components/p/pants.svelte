<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2sfgu9ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2sfgu9ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:pants" {...props}></Icon>
