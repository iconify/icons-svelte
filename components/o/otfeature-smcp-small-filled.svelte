<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpj3yzbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fpj3yzbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:otfeature-smcp-small-filled" {...props}></Icon>
