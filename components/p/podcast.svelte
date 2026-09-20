<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czri60elz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="czri60elz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:podcast" {...props}></Icon>
