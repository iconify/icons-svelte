<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7_i8lbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="n7_i8lbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:panels-fill-12" {...props}></Icon>
