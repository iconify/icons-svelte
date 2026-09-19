<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/y1zn9zwza.css';
import '../../css/o/oyjg--ejj.css';
import '../../css/t/t5xh3is5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y1zn9zwza"/><circle class="oyjg--ejj"/><path class="t5xh3is5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:monitor-dot" {...props}></Icon>
