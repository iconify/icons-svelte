<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddpn2rbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="ddpn2rbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:box-light-round-up-left" {...props}></Icon>
