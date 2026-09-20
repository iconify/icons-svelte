<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbxbaodhg.css';
import '../../css/i/iu6f4fumb.css';
import '../../css/z/zs-5weoak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="vbxbaodhg"><circle class="iu6f4fumb"/><path class="zs-5weoak"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:key-duotone-line" {...props}></Icon>
