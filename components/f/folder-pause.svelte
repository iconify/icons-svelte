<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr0kbqbko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dr0kbqbko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:folder-pause" {...props}></Icon>
