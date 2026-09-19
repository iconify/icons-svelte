<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1q1bljxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t1q1bljxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dock-bottom-right-alt-filled" {...props}></Icon>
