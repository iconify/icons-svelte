<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oec0mgsqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oec0mgsqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:jquery" {...props}></Icon>
