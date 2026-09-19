<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cz2p8ccat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="cz2p8ccat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:asterisk" {...props}></Icon>
