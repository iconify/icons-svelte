<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7nic9mka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="i7nic9mka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:ok-box" {...props}></Icon>
