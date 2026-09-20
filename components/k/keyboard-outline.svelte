<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxt8p2blw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxt8p2blw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:keyboard-outline" {...props}></Icon>
