<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t6bcjsuzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6bcjsuzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:programming-hold-code-2-bold" {...props}></Icon>
