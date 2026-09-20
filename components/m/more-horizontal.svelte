<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/u/u9jxybcpr.css';
import '../../css/x/xs7xanrwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="u9jxybcpr"/><path vector-effect="non-scaling-stroke" class="xs7xanrwc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:more-horizontal" {...props}></Icon>
