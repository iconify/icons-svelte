<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngl1ebc7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ngl1ebc7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:left-hook-arrow-filled" {...props}></Icon>
