<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4_8vnbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l4_8vnbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:app-store" {...props}></Icon>
