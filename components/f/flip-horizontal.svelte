<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u7d_wqbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u7d_wqbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flip-horizontal" {...props}></Icon>
