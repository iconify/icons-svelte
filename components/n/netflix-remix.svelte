<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g3mqs9bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="g3mqs9bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:netflix-remix" {...props}></Icon>
