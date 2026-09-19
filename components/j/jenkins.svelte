<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvys67bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":24};
const content = `<path class="mvys67bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:jenkins" {...props}></Icon>
