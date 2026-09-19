<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/ymxez2j2t.css';
import '../../css/y/y_cx2bazl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ymxez2j2t"/><path clip-rule="evenodd" class="y_cx2bazl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:device-phone-mobile-solid" {...props}></Icon>
