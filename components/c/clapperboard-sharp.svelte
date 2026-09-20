<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/erh8ajbtz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="erh8ajbtz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:clapperboard-sharp" {...props}></Icon>
