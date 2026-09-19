<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxs59cbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fxs59cbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:center-align" {...props}></Icon>
