<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl2u17qzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hl2u17qzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mobile-phone" {...props}></Icon>
