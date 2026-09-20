<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8t6515-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="c8t6515-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:logo-snapchat" {...props}></Icon>
