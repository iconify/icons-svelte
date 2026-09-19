<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb9z1ab3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bb9z1ab3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:pill" {...props}></Icon>
