<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlh-5mb2d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nlh-5mb2d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:robot-solid" {...props}></Icon>
