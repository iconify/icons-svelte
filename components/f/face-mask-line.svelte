<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l2s21khxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l2s21khxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:face-mask-line" {...props}></Icon>
