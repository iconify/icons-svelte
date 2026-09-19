<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js8wydbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="js8wydbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:caret-bottom-right-solid-8" {...props}></Icon>
