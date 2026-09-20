<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9r14fl0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e9r14fl0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:play3-filled" {...props}></Icon>
