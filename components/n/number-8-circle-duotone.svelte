<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/llper-sbd.css';
import '../../css/r/r6i16ds0i.css';
import '../../css/a/aoc0sfbxe.css';
import '../../css/g/guj4ctbxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><circle class="llper-sbd"/><circle class="r6i16ds0i"/><circle class="aoc0sfbxe"/><circle class="guj4ctbxj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-8-circle-duotone" {...props}></Icon>
