<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n65c3dbsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n65c3dbsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:menu-two-tone" {...props}></Icon>
