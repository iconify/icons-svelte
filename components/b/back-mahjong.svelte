<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itaazubme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="itaazubme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:back-mahjong" {...props}></Icon>
