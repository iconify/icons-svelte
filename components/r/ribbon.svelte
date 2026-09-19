<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrwimzbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":28,"height":32};
const content = `<path class="jrwimzbtd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="et:ribbon" {...props}></Icon>
