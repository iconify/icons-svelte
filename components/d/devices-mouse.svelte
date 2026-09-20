<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu51u7m2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="vu51u7m2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-mouse" {...props}></Icon>
