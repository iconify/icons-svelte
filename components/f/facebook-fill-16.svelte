<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p97jexevo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p97jexevo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:facebook-fill-16" {...props}></Icon>
