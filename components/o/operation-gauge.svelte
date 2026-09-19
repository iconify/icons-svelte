<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7_ef0bll.css';
import '../../css/w/ww0v738xa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b7_ef0bll"/><path class="ww0v738xa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:operation-gauge" {...props}></Icon>
