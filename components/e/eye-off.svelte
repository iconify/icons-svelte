<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/w/wl_rm_b1u.css';
import '../../css/q/qewkw1bch.css';
import '../../css/t/tzn5-tbgj.css';
import '../../css/j/j6y_b4ril.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="wl_rm_b1u"/><path class="qewkw1bch"/><path class="tzn5-tbgj"/><path class="j6y_b4ril"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:eye-off" {...props}></Icon>
