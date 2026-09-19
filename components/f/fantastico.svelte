<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv43bx5pq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="jv43bx5pq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:fantastico" {...props}></Icon>
