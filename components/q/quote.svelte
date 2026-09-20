<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0p10dgla.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b0p10dgla"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:quote" {...props}></Icon>
