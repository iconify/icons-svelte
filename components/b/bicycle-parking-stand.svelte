<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hl4atjbsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hl4atjbsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:bicycle-parking-stand" {...props}></Icon>
