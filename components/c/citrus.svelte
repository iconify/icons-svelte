<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/ruvu4yxzk.css';
import '../../css/i/i1cd8bsmc.css';
import '../../css/i/iexuhfb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ruvu4yxzk"/><path class="i1cd8bsmc"/><path class="iexuhfb5w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:citrus" {...props}></Icon>
