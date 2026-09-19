<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgu2-5bel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xgu2-5bel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:link-fill-16" {...props}></Icon>
