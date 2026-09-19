<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/snfej5b-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="snfej5b-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:nine-of-bamboos-mahjong-filled" {...props}></Icon>
