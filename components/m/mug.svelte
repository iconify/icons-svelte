<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiozjq8dd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fiozjq8dd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:mug" {...props}></Icon>
