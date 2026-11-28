<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjma9vazq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjma9vazq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:key-refresh" {...props}></Icon>
