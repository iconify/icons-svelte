<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eb2l4ubgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eb2l4ubgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:qzone" {...props}></Icon>
