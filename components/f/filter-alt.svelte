<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muvjibw6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muvjibw6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:filter-alt" {...props}></Icon>
