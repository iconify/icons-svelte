<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dljtzbc7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dljtzbc7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:no-mobile-phones" {...props}></Icon>
