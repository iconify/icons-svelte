<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xepbup7xz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xepbup7xz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-z1-pro-1" {...props}></Icon>
