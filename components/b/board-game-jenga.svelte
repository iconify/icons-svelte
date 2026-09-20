<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/rn_0s_bdl.css';
import '../../css/r/rzq8dvbgl.css';
import '../../css/q/q1ijj6hsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rn_0s_bdl"/><path class="rzq8dvbgl"/><path class="q1ijj6hsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:board-game-jenga" {...props}></Icon>
