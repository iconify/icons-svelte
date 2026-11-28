<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl9-2dg7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pl9-2dg7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:id-card-check" {...props}></Icon>
