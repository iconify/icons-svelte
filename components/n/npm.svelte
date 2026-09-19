<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpg-6cfio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jpg-6cfio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:npm" {...props}></Icon>
