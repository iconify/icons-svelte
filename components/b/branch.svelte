<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flgyrexts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="flgyrexts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:branch" {...props}></Icon>
