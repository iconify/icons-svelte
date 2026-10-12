<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/auo9mbc2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="auo9mbc2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:arrow-left-sm-20" {...props}></Icon>
