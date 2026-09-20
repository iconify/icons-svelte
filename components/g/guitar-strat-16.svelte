<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9eh8ivin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j9eh8ivin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:guitar-strat-16" {...props}></Icon>
