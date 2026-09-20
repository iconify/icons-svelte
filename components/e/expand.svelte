<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js0k_jnzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="js0k_jnzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:expand" {...props}></Icon>
