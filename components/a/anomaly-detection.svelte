<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b15xjgb5x.css';
import '../../css/c/c50_lwbrj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="b15xjgb5x"/><path class="c50_lwbrj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:anomaly-detection" {...props}></Icon>
