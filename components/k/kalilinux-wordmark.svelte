<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3qu3rbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a3qu3rbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:kalilinux-wordmark" {...props}></Icon>
