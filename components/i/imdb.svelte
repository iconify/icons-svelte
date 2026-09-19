<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l92m32boa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="l92m32boa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:imdb" {...props}></Icon>
