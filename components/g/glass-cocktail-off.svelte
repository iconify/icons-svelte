<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtl3owgka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtl3owgka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:glass-cocktail-off" {...props}></Icon>
