<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aib_ceqhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aib_ceqhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:phone-call-speaker-stroke-16" {...props}></Icon>
