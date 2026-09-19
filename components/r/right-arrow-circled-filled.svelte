<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqt70smsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="dqt70smsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:right-arrow-circled-filled" {...props}></Icon>
