<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq-azk5il.css';
import '../../css/z/zu7-jfbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lq-azk5il"/><path class="zu7-jfbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:django" {...props}></Icon>
