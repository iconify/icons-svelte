<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8dec0bkn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g8dec0bkn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:new-moon" {...props}></Icon>
