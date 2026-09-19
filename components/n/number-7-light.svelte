<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwkakl2fm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwkakl2fm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:number-7-light" {...props}></Icon>
