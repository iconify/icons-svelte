<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/c/cec2pqbum.css';
import '../../css/z/zaius3qog.css';
import '../../css/r/rvymobzlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cec2pqbum"/><path class="zaius3qog"/><path class="rvymobzlx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:hierarchy-square" {...props}></Icon>
