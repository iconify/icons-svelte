<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su6l7fbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1792};
const content = `<path class="su6l7fbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:hourglass" {...props}></Icon>
