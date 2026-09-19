<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/f/fx_zu3nnm.css';
import '../../css/g/gvie50bbb.css';
import '../../css/s/svio-1bwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="fx_zu3nnm"/><path class="gvie50bbb"/><path class="svio-1bwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:attention-square-bold" {...props}></Icon>
