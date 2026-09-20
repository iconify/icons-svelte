<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9gpu_b2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v9gpu_b2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:crater" {...props}></Icon>
