<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nclr7z71f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="nclr7z71f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:ethernet" {...props}></Icon>
