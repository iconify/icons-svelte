<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j8jmoab7b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j8jmoab7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:database-remove" {...props}></Icon>
