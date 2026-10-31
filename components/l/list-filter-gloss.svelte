<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-_crhbid.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-_crhbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:list-filter-gloss" {...props}></Icon>
