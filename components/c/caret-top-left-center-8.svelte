<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ljm7f5bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ljm7f5bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-top-left-center-8" {...props}></Icon>
