<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcoxt7ego.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jcoxt7ego"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:app-window-x" {...props}></Icon>
