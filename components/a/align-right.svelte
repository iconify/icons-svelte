<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x-x03nb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="x-x03nb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:align-right" {...props}></Icon>
