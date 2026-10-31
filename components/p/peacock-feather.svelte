<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/b/b9v2r3b5c.css';
import '../../css/e/ecrul3biy.css';
import '../../css/t/tzf16xm0i.css';
import '../../css/v/v-ytw7mjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="b9v2r3b5c wm-shadow"/><path class="ecrul3biy wm-shadow"/><path class="tzf16xm0i"/><path class="v-ytw7mjk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:peacock-feather" {...props}></Icon>
