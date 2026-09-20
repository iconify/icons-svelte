<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/k/kmj_7ubfc.css';
import '../../css/l/lx14d1bki.css';
import '../../css/u/u3r5afb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kmj_7ubfc"/><path class="lx14d1bki"/><path class="u3r5afb8y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:messages2" {...props}></Icon>
