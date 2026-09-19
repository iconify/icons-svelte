<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-1qibqbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h-1qibqbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:border-bl" {...props}></Icon>
