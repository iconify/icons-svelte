<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3e-q4b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3e-q4b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:perspective-view" {...props}></Icon>
