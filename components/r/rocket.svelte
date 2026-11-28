<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9kd0qb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j9kd0qb1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:rocket" {...props}></Icon>
