<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8z7-1_ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n8z7-1_ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:abstract" {...props}></Icon>
