<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to-5kdesz.css';
import '../../css/f/fx_zu3nnm.css';
import '../../css/q/qqec_9bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="to-5kdesz"><path class="fx_zu3nnm"/><path class="qqec_9bvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:menu-kebab-horizontal-square-bold" {...props}></Icon>
