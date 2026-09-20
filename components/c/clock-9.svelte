<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibwv3bt8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibwv3bt8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:clock-9" {...props}></Icon>
