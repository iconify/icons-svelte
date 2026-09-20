<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpvag-22g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fpvag-22g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:ctrl" {...props}></Icon>
