<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8ugbvd9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="i8ugbvd9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:message-tick-outline" {...props}></Icon>
