<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ookuxubeg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="ookuxubeg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:next-step-2" {...props}></Icon>
