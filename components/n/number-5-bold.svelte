<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9vdr7-qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9vdr7-qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-5-bold" {...props}></Icon>
