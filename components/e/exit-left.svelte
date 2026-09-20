<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wudkh2r8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="wudkh2r8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:exit-left" {...props}></Icon>
