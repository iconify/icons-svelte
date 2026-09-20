<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/g1ygkpenk.css';
import '../../css/e/eq4ku8q_n.css';
import '../../css/q/q58jyg4uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g1ygkpenk"/><path class="eq4ku8q_n"/><circle class="q58jyg4uk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ball-basket" {...props}></Icon>
