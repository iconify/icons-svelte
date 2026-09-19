<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pn9b94bna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="pn9b94bna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:play" {...props}></Icon>
