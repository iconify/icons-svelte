<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tla653boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tla653boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:laptop" {...props}></Icon>
