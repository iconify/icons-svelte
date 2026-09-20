<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/r97pm5uic.css';
import '../../css/l/lhny41bxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="r97pm5uic"/><path class="lhny41bxk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:nap" {...props}></Icon>
