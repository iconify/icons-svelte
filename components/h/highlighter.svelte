<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ez5rt2sqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ez5rt2sqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:highlighter" {...props}></Icon>
