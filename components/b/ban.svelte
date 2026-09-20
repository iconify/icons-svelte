<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duj4s1--s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="duj4s1--s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:ban" {...props}></Icon>
