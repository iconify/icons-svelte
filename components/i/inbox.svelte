<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5huyu70j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":750};
const content = `<path class="c5huyu70j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:inbox" {...props}></Icon>
