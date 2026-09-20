<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px063k46p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px063k46p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:border-inner" {...props}></Icon>
