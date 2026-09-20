<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3jurt13t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3jurt13t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:arrow-big-left" {...props}></Icon>
