<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he5lwbciq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he5lwbciq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-outdoor-string" {...props}></Icon>
