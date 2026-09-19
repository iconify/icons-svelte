<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg1eho4bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg1eho4bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:menu-grid-r" {...props}></Icon>
