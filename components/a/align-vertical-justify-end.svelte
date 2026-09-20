<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9udfcbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i9udfcbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:align-vertical-justify-end" {...props}></Icon>
