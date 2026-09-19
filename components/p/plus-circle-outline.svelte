<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/y/ytkds-bxy.css';
import '../../css/l/lc3kdubbj.css';
import '../../css/t/tgva9kbpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="plus-circle-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="ytkds-bxy"/><path class="lc3kdubbj"/><path class="tgva9kbpr"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:plus-circle-outline" {...props}></Icon>
