<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/p/psncsiz9v.css';
import '../../css/h/hjixulbzq.css';
import '../../css/a/a3525ioso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="psncsiz9v"/><path class="hjixulbzq"/><path class="a3525ioso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:kappa" {...props}></Icon>
