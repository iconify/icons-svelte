<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zetc7ib7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zetc7ib7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:list-ul" {...props}></Icon>
