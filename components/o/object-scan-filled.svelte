<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/f01lhjzea.css';
import '../../css/k/k2jkwyg1s.css';
import '../../css/n/n7it1melf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f01lhjzea"/><path clip-rule="evenodd" class="k2jkwyg1s"/><path class="n7it1melf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:object-scan-filled" {...props}></Icon>
