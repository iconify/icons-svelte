<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c2rg7xbog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="c2rg7xbog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:banknote-fill-16" {...props}></Icon>
