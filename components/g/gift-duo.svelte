<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k5hkbv56d.css';
import '../../css/j/j8_x8iboc.css';
import '../../css/w/w8x39x84j.css';
import '../../css/q/qiyypgbtt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k5hkbv56d"/><path class="j8_x8iboc wm-a"/><path class="w8x39x84j wm-a"/><path class="qiyypgbtt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:gift-duo" {...props}></Icon>
