<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bltctjbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":559,"height":671};
const content = `<path class="bltctjbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:e" {...props}></Icon>
