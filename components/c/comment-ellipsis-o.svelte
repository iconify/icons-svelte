<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nc8ninjpx.css';
import '../../css/e/epg14abwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="nc8ninjpx"/><path class="epg14abwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:comment-ellipsis-o" {...props}></Icon>
