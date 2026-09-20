<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3dgnqbha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3dgnqbha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cookie-man" {...props}></Icon>
