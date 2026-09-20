<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hgun8acjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="hgun8acjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:panel-left" {...props}></Icon>
