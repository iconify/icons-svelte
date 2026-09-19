<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whko7vb-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="whko7vb-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:die-one" {...props}></Icon>
