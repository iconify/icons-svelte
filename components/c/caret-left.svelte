<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mm7bv5bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mm7bv5bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caret-left" {...props}></Icon>
