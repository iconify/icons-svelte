<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yw2yiybqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="yw2yiybqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:pause-circle-o" {...props}></Icon>
