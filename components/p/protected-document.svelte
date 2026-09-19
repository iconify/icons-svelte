<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku-7y90xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ku-7y90xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:protected-document" {...props}></Icon>
