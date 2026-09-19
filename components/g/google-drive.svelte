<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ekeukp4zn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ekeukp4zn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo-social:google-drive" {...props}></Icon>
