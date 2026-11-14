<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/ibd-53qeo.css';
import '../../css/x/xjm_pacui.css';
import '../../css/u/u3h2dubyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="ibd-53qeo"/><path class="xjm_pacui"/><path class="u3h2dubyj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:charging-card" {...props}></Icon>
