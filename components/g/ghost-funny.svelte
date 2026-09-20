<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/lqs17vbsb.css';
import '../../css/j/j3f-cqwca.css';
import '../../css/r/rlsuisb1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lqs17vbsb"/><path class="j3f-cqwca"/><path class="rlsuisb1c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:ghost-funny" {...props}></Icon>
