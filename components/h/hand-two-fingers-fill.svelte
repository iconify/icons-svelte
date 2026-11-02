<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5i6fdbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s5i6fdbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-two-fingers-fill" {...props}></Icon>
