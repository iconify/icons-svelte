<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvujvo0-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vvujvo0-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:navigation-flipper" {...props}></Icon>
