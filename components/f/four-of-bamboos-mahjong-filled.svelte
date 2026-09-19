<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hob4cnbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hob4cnbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:four-of-bamboos-mahjong-filled" {...props}></Icon>
