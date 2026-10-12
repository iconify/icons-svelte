<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wvo8mpb5j.css';
import '../../css/i/iym-rnbyp.css';
import '../../css/i/i_ejbbcyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wvo8mpb5j"/><path class="iym-rnbyp"/><path class="i_ejbbcyc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:message-square-diff-duotone" {...props}></Icon>
