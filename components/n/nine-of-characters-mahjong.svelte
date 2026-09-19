<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz9aracnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kz9aracnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:nine-of-characters-mahjong" {...props}></Icon>
