<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3l2b5bal.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="l3l2b5bal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:adjustments-filled" {...props}></Icon>
