<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hk1lm37nu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="hk1lm37nu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:qq-filled" {...props}></Icon>
