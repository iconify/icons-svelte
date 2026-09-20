<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqf9kac9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yqf9kac9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:file-13" {...props}></Icon>
