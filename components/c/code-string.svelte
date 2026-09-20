<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kadgbhn0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kadgbhn0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:code-string" {...props}></Icon>
