<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/b/bsoq4zgli.css';
import '../../css/i/iqv0xnyvl.css';
import '../../css/d/d3nxyvb1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="bsoq4zgli"/><path class="iqv0xnyvl"/><path class="d3nxyvb1i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:milkshake-flat" {...props}></Icon>
