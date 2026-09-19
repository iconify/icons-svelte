<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2pp3cbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f2pp3cbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-2-thin" {...props}></Icon>
