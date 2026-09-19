<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-um8lqro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-um8lqro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chart-area" {...props}></Icon>
