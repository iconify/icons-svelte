<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6p7f05an.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="j6p7f05an"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:mobile-phone-alt2" {...props}></Icon>
