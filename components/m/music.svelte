<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w9660gbgl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="w9660gbgl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:music" {...props}></Icon>
