<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bzs052bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1022,"height":1024};
const content = `<path class="bzs052bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dog" {...props}></Icon>
