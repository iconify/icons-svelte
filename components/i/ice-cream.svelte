<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9ms98rdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="b9ms98rdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:ice-cream" {...props}></Icon>
