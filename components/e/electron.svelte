<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cqcd_1b7g.css';
import '../../css/o/oiny4j3cd.css';
import '../../css/o/onmyc1b4h.css';
import '../../css/w/w-cmwjbvu.css';
import '../../css/w/wqndocb7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<g class="cqcd_1b7g"><path class="oiny4j3cd"/><path class="onmyc1b4h"/><path class="w-cmwjbvu"/><path class="wqndocb7y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:electron" {...props}></Icon>
