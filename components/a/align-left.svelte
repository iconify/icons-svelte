<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8y7n0fxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="a8y7n0fxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:align-left" {...props}></Icon>
