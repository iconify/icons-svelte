<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skglo3xlk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="skglo3xlk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:pizza" {...props}></Icon>
