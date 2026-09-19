<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qoi3q_b_l.css';
import '../../css/w/w9c6qv_hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qoi3q_b_l"/><path class="w9c6qv_hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:add-alt" {...props}></Icon>
