<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qphvnvb7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qphvnvb7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:chevron-left-small" {...props}></Icon>
