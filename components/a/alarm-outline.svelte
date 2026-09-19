<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/u/u8d1-xbtn.css';
import '../../css/a/a7-t3rc7m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="u8d1-xbtn"/><path class="a7-t3rc7m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:alarm-outline" {...props}></Icon>
