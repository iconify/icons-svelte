<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/f/fdl8bldpc.css';
import '../../css/m/m-9wagvil.css';
import '../../css/l/lo6nx5rwy.css';
import '../../css/x/xrgx2dblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="fdl8bldpc"/><path class="m-9wagvil"/><path class="lo6nx5rwy"/><path class="xrgx2dblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:clock-circle" {...props}></Icon>
