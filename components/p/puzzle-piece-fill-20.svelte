<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e00ealyrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e00ealyrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:puzzle-piece-fill-20" {...props}></Icon>
