<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex2nu4occ.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="ex2nu4occ"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:mini-link" {...props}></Icon>
