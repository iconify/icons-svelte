<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aodq9y6zp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aodq9y6zp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:github-box" {...props}></Icon>
