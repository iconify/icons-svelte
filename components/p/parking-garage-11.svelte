<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/puvxshblk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="puvxshblk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:parking-garage-11" {...props}></Icon>
