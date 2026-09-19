<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci8phsb1v.css';
import '../../css/r/rzz4edc1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ci8phsb1v"/><path class="rzz4edc1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:megaphone-stroke-16" {...props}></Icon>
