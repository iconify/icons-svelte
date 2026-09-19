<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vigo633vd.css';
import '../../css/i/ie7387b1v.css';
import '../../css/u/un3wu1fqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vigo633vd"/><path class="ie7387b1v"/><path class="un3wu1fqw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:heart-hands-duo" {...props}></Icon>
