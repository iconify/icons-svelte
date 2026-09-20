<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dujg6qgto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dujg6qgto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-d20" {...props}></Icon>
