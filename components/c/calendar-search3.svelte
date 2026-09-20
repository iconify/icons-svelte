<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/e/e51pb7v-v.css';
import '../../css/h/hvgzjjb7d.css';
import '../../css/f/fsdh34bfl.css';
import '../../css/a/ajqhpcbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e51pb7v-v"/><path class="hvgzjjb7d"/><path class="fsdh34bfl"/><path class="ajqhpcbca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-search3" {...props}></Icon>
