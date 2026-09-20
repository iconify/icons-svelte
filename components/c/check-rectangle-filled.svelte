<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tvji5lkkx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tvji5lkkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:check-rectangle-filled" {...props}></Icon>
