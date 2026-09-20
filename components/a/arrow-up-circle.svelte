<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4_0yrkqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z4_0yrkqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:arrow-up-circle" {...props}></Icon>
