<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adhe8v3hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="adhe8v3hy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:prescription-bottle-alt" {...props}></Icon>
