<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bkbgjrbao.css';
import '../../css/k/k6rstmvnk.css';
import '../../css/h/hhj58fbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bkbgjrbao"/><path class="k6rstmvnk"/><path class="hhj58fbib"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fingerprint-lock-circle" {...props}></Icon>
