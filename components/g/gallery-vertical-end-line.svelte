<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex-auqnvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex-auqnvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gallery-vertical-end-line" {...props}></Icon>
