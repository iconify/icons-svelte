<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qveylgb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qveylgb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:java" {...props}></Icon>
