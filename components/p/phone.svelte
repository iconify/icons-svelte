<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vmvqur1fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vmvqur1fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:phone" {...props}></Icon>
