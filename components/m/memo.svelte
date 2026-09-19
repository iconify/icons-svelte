<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp95lcb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="tp95lcb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:memo" {...props}></Icon>
