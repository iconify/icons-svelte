<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a1-owzbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="a1-owzbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:linux" {...props}></Icon>
