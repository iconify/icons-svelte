<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8j-v7bth.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z8j-v7bth"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-list-square-fill-20" {...props}></Icon>
