<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g96qynbtf.css';
import '../../css/y/yqg61wbkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g96qynbtf"/><path class="yqg61wbkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:reactor-20" {...props}></Icon>
