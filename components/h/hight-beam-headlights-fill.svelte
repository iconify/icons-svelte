<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opikm--fj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opikm--fj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hight-beam-headlights-fill" {...props}></Icon>
