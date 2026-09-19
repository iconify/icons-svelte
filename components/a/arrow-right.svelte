<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjle_n9oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mjle_n9oj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:arrow-right" {...props}></Icon>
