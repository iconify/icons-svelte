<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhz5i4bfl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="vhz5i4bfl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:chestnut" {...props}></Icon>
