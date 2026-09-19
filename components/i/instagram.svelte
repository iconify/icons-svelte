<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnxov3bbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnxov3bbl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:instagram" {...props}></Icon>
