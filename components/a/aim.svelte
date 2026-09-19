<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bz4gnyzmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":569,"height":694};
const content = `<path class="bz4gnyzmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:aim" {...props}></Icon>
