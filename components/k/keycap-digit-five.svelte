<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k0_rb3l7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="k0_rb3l7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:keycap-digit-five" {...props}></Icon>
