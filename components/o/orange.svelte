<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl140fphs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fl140fphs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:orange" {...props}></Icon>
