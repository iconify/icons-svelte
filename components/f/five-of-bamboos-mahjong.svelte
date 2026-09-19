<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sum2o0bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sum2o0bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:five-of-bamboos-mahjong" {...props}></Icon>
