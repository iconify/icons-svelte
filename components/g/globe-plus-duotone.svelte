<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hm0z84mqz.css';
import '../../css/i/im-u2lvxf.css';
import '../../css/r/rzklukbol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hm0z84mqz"/><path class="im-u2lvxf"/><path class="rzklukbol"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:globe-plus-duotone" {...props}></Icon>
