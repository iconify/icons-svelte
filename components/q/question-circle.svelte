<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba7_2s_nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ba7_2s_nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:question-circle" {...props}></Icon>
