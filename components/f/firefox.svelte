<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm5pvq32z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mm5pvq32z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:firefox" {...props}></Icon>
