<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3y51acpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f3y51acpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:dribbble" {...props}></Icon>
