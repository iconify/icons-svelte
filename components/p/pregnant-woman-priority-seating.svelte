<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj6zyvo6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj6zyvo6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:pregnant-woman-priority-seating" {...props}></Icon>
