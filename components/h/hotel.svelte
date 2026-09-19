<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zpp4vf5pi.css';
import '../../css/q/qhx66epws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zpp4vf5pi"/><path class="qhx66epws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hotel" {...props}></Icon>
