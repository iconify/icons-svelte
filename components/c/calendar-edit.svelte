<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/o79ijpb8u.css';
import '../../css/z/zqnchacxh.css';
import '../../css/a/ajqhpcbca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o79ijpb8u"/><path class="zqnchacxh"/><path class="ajqhpcbca"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calendar-edit" {...props}></Icon>
