<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aeehi_bkg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aeehi_bkg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:plug-type-l" {...props}></Icon>
