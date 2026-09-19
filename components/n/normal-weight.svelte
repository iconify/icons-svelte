<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x8aw9gdat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="x8aw9gdat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:normal-weight" {...props}></Icon>
