<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap4nx0b0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ap4nx0b0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:left-circle-outline" {...props}></Icon>
