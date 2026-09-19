<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bct1xkbdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bct1xkbdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:dessert" {...props}></Icon>
