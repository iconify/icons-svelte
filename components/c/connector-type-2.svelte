<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9zd7pbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v9zd7pbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:connector-type-2" {...props}></Icon>
