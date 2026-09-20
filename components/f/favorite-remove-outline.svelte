<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jlacjk0py.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jlacjk0py"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:favorite-remove-outline" {...props}></Icon>
