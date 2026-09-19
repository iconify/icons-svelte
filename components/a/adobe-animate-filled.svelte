<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wp9pt-bnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="wp9pt-bnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adobe-animate-filled" {...props}></Icon>
