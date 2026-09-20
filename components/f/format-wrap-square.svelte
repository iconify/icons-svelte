<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd4bqtbvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd4bqtbvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-wrap-square" {...props}></Icon>
