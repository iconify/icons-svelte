<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bup2b6b2v.css';
import '../../css/p/pt8jm_b_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bup2b6b2v"/><path class="pt8jm_b_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:calendar" {...props}></Icon>
