<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngyz1ybdb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ngyz1ybdb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:dribbblealt" {...props}></Icon>
