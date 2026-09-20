<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfp9bv07i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfp9bv07i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:letter-x" {...props}></Icon>
