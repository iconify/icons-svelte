<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trlqebcfp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="trlqebcfp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-split" {...props}></Icon>
