<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b41e93k-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b41e93k-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:na-line" {...props}></Icon>
