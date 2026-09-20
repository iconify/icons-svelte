<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/it07qtb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="it07qtb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ornament-variant" {...props}></Icon>
