<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5i3wzbfe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="l5i3wzbfe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:file-movie-o" {...props}></Icon>
