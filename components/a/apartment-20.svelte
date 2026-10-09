<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdirvfh-u.css';
import '../../css/r/r60z8bcvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cdirvfh-u"/><path class="r60z8bcvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:apartment-20" {...props}></Icon>
