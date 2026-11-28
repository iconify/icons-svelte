<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htwqw0bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htwqw0bda primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:arrow-left-through-line-duotone" {...props}></Icon>
