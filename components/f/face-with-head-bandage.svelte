<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xus7n3b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="xus7n3b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:face-with-head-bandage" {...props}></Icon>
