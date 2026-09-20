<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-0ql8beu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o-0ql8beu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:connectdevelop" {...props}></Icon>
