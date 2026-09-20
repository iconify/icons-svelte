<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/beprfqbna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="beprfqbna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-disk-cd-1" {...props}></Icon>
