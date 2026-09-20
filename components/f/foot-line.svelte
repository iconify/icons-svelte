<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsxbycckc.css';
import '../../css/i/i4nhh7ann.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsxbycckc"/><path class="i4nhh7ann"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:foot-line" {...props}></Icon>
