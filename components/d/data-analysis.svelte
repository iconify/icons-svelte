<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-vvnbbpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="f-vvnbbpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:data-analysis" {...props}></Icon>
