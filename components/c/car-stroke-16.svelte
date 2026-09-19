<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq-e9ebei.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jq-e9ebei"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:car-stroke-16" {...props}></Icon>
