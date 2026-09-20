<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdggzp0fi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cdggzp0fi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:envelope-open" {...props}></Icon>
