<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2ru_1ven.css';
import '../../css/c/cpjb_5hdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2ru_1ven"/><path class="cpjb_5hdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:location-fill" {...props}></Icon>
