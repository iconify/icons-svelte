<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruajt4b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ruajt4b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:education" {...props}></Icon>
