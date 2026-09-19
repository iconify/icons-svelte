<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7j3vib8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":24};
const content = `<path class="n7j3vib8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:aids" {...props}></Icon>
