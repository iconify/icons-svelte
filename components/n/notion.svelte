<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdg_z8g7j.css';
import '../../css/m/m3bb8qa6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdg_z8g7j"/><path class="m3bb8qa6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:notion" {...props}></Icon>
