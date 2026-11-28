<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtjs5r6lh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtjs5r6lh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:euro" {...props}></Icon>
