<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6-8ukwdo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6-8ukwdo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:neon" {...props}></Icon>
