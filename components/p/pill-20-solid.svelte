<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp6svgb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cp6svgb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pill-20-solid" {...props}></Icon>
