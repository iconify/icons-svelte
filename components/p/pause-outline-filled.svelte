<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_4vr29tc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i_4vr29tc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:pause-outline-filled" {...props}></Icon>
