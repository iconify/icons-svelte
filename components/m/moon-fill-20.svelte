<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c4sk49bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="c4sk49bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:moon-fill-20" {...props}></Icon>
