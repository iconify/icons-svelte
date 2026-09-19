<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/frkxnd0nd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":596,"height":717};
const content = `<path class="frkxnd0nd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:album" {...props}></Icon>
