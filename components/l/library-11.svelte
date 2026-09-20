<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c1zhb0bqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="c1zhb0bqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:library-11" {...props}></Icon>
