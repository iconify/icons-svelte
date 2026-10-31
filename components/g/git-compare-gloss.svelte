<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6509kg3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6509kg3l wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-compare-gloss" {...props}></Icon>
