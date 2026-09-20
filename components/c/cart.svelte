<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jtzqtmbpa.css';
import '../../css/x/xv2mki75f.css';
import '../../css/x/x2vknkufc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="jtzqtmbpa"/><circle class="xv2mki75f"/><path class="x2vknkufc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:cart" {...props}></Icon>
