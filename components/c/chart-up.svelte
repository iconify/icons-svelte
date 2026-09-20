<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfz6qmbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfz6qmbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:chart-up" {...props}></Icon>
