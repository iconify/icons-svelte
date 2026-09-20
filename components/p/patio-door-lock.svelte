<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hea445i6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hea445i6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:patio-door-lock" {...props}></Icon>
