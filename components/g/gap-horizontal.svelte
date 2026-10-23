<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqec03jgb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tqec03jgb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gap-horizontal" {...props}></Icon>
