<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/i/i1sg4lbhw.css';
import '../../css/r/r0jd0fpwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="i1sg4lbhw"/><path class="r0jd0fpwr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:qtcon" {...props}></Icon>
