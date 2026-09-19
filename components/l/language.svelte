<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogp5jpblq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ogp5jpblq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:language" {...props}></Icon>
