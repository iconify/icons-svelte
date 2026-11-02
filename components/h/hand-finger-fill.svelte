<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kleeicbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kleeicbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-finger-fill" {...props}></Icon>
