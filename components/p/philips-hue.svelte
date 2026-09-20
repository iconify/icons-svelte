<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx6x4gb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jx6x4gb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:philips-hue" {...props}></Icon>
