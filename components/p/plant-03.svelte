<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/u/ucmf90w8w.css';
import '../../css/r/rpipyf98w.css';
import '../../css/d/dks-6wcfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ucmf90w8w"/><path class="rpipyf98w"/><path class="dks-6wcfg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:plant-03" {...props}></Icon>
