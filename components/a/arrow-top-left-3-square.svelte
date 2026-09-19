<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0f3uzzwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0f3uzzwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:arrow-top-left-3-square" {...props}></Icon>
