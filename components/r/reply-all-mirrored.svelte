<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvt71zbsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="dvt71zbsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:reply-all-mirrored" {...props}></Icon>
