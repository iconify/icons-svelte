<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7qdbqe7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r7qdbqe7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:jameson" {...props}></Icon>
