<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoh8w0bzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoh8w0bzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:package-line" {...props}></Icon>
