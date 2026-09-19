<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/am7v8ubau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="am7v8ubau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:increase-indent-legacy" {...props}></Icon>
