<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq5bn3vbw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gq5bn3vbw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:battery-alert" {...props}></Icon>
