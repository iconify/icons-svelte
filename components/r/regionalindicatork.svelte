<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anoz2ab7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anoz2ab7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:regionalindicatork" {...props}></Icon>
