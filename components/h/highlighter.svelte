<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_x77tb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="q_x77tb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:highlighter" {...props}></Icon>
