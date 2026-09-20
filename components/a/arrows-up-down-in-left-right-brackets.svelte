<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmd7zetxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dmd7zetxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-up-down-in-left-right-brackets" {...props}></Icon>
