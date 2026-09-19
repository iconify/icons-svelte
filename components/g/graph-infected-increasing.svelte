<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/j/jt23tkppp.css';
import '../../css/h/hrmz_5b-w.css';
import '../../css/o/orc4cutqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jt23tkppp"/><path class="hrmz_5b-w"/><path class="orc4cutqc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:graph-infected-increasing" {...props}></Icon>
