<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pqhqrlbqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pqhqrlbqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:dragons-teeth" {...props}></Icon>
