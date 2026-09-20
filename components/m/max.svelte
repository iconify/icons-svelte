<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zp4e3acvk.css';
import '../../css/o/ogw4cx2sz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="zp4e3acvk"/><path class="ogw4cx2sz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:max" {...props}></Icon>
