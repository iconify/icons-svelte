<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni46c40-i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ni46c40-i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:fax-machine" {...props}></Icon>
