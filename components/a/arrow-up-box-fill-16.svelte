<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fckspfb8v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fckspfb8v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-up-box-fill-16" {...props}></Icon>
