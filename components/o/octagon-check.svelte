<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tskuybc5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tskuybc5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:octagon-check" {...props}></Icon>
