<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j91tljbil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j91tljbil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:branch" {...props}></Icon>
