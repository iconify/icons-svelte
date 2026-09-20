<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qczze5bto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path clip-rule="evenodd" class="qczze5bto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:highlighter-2" {...props}></Icon>
