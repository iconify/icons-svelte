<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlllpobll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlllpobll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:projector-screen-off" {...props}></Icon>
