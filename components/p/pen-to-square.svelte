<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv0kxeboj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jv0kxeboj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:pen-to-square" {...props}></Icon>
