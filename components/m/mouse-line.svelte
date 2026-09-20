<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jr2x1qb7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jr2x1qb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:mouse-line" {...props}></Icon>
