<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu0jkqbek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pu0jkqbek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:mouse-move-up" {...props}></Icon>
