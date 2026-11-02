<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8906rbdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j8906rbdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:numbers-09-sort-descending-line" {...props}></Icon>
