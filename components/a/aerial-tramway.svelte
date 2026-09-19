<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/njfbn0bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="njfbn0bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:aerial-tramway" {...props}></Icon>
