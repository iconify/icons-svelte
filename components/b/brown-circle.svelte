<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ika2pmy3d.css';
import '../../css/s/snpiwsb_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="ika2pmy3d"/><circle class="snpiwsb_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:brown-circle" {...props}></Icon>
