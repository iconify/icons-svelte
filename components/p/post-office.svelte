<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjoe9x-2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="jjoe9x-2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:post-office" {...props}></Icon>
