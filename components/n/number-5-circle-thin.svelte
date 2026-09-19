<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/m/m4l-9ybuj.css';
import '../../css/f/f629m7bdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><circle class="m4l-9ybuj"/><path class="f629m7bdx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-5-circle-thin" {...props}></Icon>
