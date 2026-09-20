<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6che1bpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6che1bpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:artboard-2-line" {...props}></Icon>
