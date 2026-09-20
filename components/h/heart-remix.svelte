<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0sb-hbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b0sb-hbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:heart-remix" {...props}></Icon>
