<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/p/pa3guob9q.css';
import '../../css/p/pl1bqabkz.css';
import '../../css/e/eweuc1kpp.css';
import '../../css/d/dja1jdboi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="wwvp95byt"><path clip-rule="evenodd" class="pa3guob9q"/><path class="pl1bqabkz"/><path class="eweuc1kpp"/><path class="dja1jdboi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:building-three" {...props}></Icon>
