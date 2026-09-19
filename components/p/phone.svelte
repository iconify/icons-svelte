<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/u/ujed1zb_y.css';
import '../../css/w/wwxsycqox.css';
import '../../css/o/os5lo5ptn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><path class="ujed1zb_y"/><path class="wwxsycqox"/><path class="os5lo5ptn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:phone" {...props}></Icon>
