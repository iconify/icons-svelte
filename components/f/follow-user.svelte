<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a81gz4b4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="a81gz4b4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:follow-user" {...props}></Icon>
