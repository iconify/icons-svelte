<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t71s4gkgz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t71s4gkgz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-chevron-right-gloss" {...props}></Icon>
