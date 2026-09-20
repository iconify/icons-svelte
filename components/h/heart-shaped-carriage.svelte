<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qksruit4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qksruit4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:heart-shaped-carriage" {...props}></Icon>
