<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miq6brhkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="miq6brhkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:chess-bishop" {...props}></Icon>
