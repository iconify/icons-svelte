<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5p1ufkjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="t5p1ufkjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:phone-slash" {...props}></Icon>
