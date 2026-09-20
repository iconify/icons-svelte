<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x5hwhv6mp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="x5hwhv6mp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:disable-heart-remix" {...props}></Icon>
