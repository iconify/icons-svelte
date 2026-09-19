<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/yi_ml2bts.css';
import '../../css/f/frw1ezbng.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="yi_ml2bts"/><path class="frw1ezbng"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:plurk-alt" {...props}></Icon>
