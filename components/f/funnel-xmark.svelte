<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4iq1f7zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w4iq1f7zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:funnel-xmark" {...props}></Icon>
