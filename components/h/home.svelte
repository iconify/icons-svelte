<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li3cydawl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="li3cydawl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:home" {...props}></Icon>
