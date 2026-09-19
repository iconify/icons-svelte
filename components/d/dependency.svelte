<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy9xnq4db.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jy9xnq4db"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:dependency" {...props}></Icon>
