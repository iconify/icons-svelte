<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lkd_gcbtf.css';
import '../../css/f/f421e3bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lkd_gcbtf"/><path class="f421e3bkk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:palm" {...props}></Icon>
