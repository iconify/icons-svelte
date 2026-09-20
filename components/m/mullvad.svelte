<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imprk8tlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imprk8tlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:mullvad" {...props}></Icon>
