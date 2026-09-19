<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3-_e5b5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":674};
const content = `<path class="p3-_e5b5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:networksignal" {...props}></Icon>
