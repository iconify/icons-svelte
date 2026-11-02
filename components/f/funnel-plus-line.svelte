<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o07qwgbzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o07qwgbzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:funnel-plus-line" {...props}></Icon>
