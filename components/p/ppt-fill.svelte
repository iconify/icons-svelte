<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgtn7raku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgtn7raku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ppt-fill" {...props}></Icon>
