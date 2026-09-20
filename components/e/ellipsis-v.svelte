<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ob3y1iinc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ob3y1iinc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ellipsis-v" {...props}></Icon>
