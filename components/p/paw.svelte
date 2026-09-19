<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2kg-3buk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j2kg-3buk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:paw" {...props}></Icon>
