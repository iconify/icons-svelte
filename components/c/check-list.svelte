<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/alds_x8qj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="alds_x8qj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:check-list" {...props}></Icon>
