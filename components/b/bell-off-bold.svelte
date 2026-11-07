<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m92zv-bjj.css';
import '../../css/d/dmh6kqbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m92zv-bjj"/><path clip-rule="evenodd" class="dmh6kqbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bell-off-bold" {...props}></Icon>
