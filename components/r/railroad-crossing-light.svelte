<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wk5-xn30x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wk5-xn30x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:railroad-crossing-light" {...props}></Icon>
