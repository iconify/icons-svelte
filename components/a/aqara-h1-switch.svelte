<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzp2s1bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzp2s1bow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-h1-switch" {...props}></Icon>
