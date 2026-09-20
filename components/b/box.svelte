<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szqwaccnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="szqwaccnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:box" {...props}></Icon>
