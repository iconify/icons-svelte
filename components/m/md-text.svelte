<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5x5m0jyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p5x5m0jyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-text" {...props}></Icon>
