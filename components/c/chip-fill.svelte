<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzt_2ac2s.css';
import '../../css/v/vyl_3wa6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jzt_2ac2s"/><path class="vyl_3wa6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chip-fill" {...props}></Icon>
