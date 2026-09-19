<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q17he9bsz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="q17he9bsz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-up-stroke-12" {...props}></Icon>
