<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmg89kv6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="mmg89kv6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:refresh" {...props}></Icon>
