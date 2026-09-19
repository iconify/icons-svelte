<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hyx4-db_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hyx4-db_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-sm-fill-16" {...props}></Icon>
