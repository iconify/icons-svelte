<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2nae0b0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h2nae0b0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:mouse-filled" {...props}></Icon>
