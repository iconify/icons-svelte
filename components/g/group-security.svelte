<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9hn6abln.css';
import '../../css/n/nsui017pl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="p9hn6abln"/><path class="nsui017pl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:group-security" {...props}></Icon>
