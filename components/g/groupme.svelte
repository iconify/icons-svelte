<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bglhwccvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bglhwccvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:groupme" {...props}></Icon>
