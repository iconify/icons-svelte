<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ukuhlz15q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ukuhlz15q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:filter-alt" {...props}></Icon>
