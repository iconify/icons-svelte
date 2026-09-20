<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aihw0sbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aihw0sbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:other-ui-megaphone" {...props}></Icon>
