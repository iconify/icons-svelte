<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb2rjqbqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cb2rjqbqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:map-arrow-up-linear" {...props}></Icon>
