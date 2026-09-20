<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z09solb1k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="z09solb1k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:badge" {...props}></Icon>
