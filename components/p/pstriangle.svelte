<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wigvr0qxq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wigvr0qxq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pstriangle" {...props}></Icon>
