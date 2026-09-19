<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g2reb_1-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="g2reb_1-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:iphone" {...props}></Icon>
