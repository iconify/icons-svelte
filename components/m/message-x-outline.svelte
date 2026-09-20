<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpfq5ioxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fpfq5ioxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-x-outline" {...props}></Icon>
