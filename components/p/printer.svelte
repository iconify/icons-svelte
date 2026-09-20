<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j2jh-x13v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="j2jh-x13v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:printer" {...props}></Icon>
