<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2ddm3b8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="t2ddm3b8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:information-barriers" {...props}></Icon>
