<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezsnwlscl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ezsnwlscl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:briefcase-with-megaphone" {...props}></Icon>
