<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca_0qsbyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ca_0qsbyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:circle-stop" {...props}></Icon>
