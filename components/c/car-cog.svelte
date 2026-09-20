<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8qewqbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o8qewqbnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:car-cog" {...props}></Icon>
