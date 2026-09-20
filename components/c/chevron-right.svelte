<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bbqgn3bju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bbqgn3bju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-right" {...props}></Icon>
