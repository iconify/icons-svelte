<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/salro-bgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="salro-bgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:refresh" {...props}></Icon>
