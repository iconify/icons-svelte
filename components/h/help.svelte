<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uu3wj5boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uu3wj5boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:help" {...props}></Icon>
