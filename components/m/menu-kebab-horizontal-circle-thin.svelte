<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/x/xr1zzs9rr.css';
import '../../css/i/i8egozbpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><circle class="xr1zzs9rr"/><path class="i8egozbpk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-horizontal-circle-thin" {...props}></Icon>
