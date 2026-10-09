<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qisnddmbb.css';
import '../../css/i/i5r18_m4w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qisnddmbb"/><path class="i5r18_m4w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hard-hat-48" {...props}></Icon>
