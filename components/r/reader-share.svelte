<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7vvir64i.css';
import '../../css/r/roi1-go0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<clipPath id="SVGWLziubJw"><path class="t7vvir64i"/></clipPath><g clip-path="url(#SVGWLziubJw)"><path class="roi1-go0j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:reader-share" {...props}></Icon>
