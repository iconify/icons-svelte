<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sla-77b4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sla-77b4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:face-mask" {...props}></Icon>
