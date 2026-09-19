<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hrbsexkbj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hrbsexkbj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:call-done" {...props}></Icon>
