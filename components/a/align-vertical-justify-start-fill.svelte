<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qznuanbfg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qznuanbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-vertical-justify-start-fill" {...props}></Icon>
