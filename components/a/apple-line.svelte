<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbiftsbcs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbiftsbcs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:apple-line" {...props}></Icon>
