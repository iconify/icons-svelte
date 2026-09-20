<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyhk6-brf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="xyhk6-brf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:align-right-1-remix" {...props}></Icon>
