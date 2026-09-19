<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc0d_ubzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":832};
const content = `<path class="fc0d_ubzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:github" {...props}></Icon>
