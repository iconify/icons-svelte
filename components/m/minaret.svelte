<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/suxzk1n9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="suxzk1n9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:minaret" {...props}></Icon>
