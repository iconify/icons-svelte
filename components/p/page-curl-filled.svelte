<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sbilb_8jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="sbilb_8jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:page-curl-filled" {...props}></Icon>
