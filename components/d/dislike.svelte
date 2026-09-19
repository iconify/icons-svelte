<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c054m9cuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c054m9cuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:dislike" {...props}></Icon>
