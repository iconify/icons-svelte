<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mad-nx4zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mad-nx4zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:flask-empty-minus" {...props}></Icon>
