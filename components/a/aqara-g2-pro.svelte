<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m03rwol8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m03rwol8t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-g2-pro" {...props}></Icon>
