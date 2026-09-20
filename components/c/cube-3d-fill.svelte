<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djhyracdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="djhyracdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cube-3d-fill" {...props}></Icon>
