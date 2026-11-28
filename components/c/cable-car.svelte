<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9hiye1kf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9hiye1kf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:cable-car" {...props}></Icon>
