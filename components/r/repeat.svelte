<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ului6db3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ului6db3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:repeat" {...props}></Icon>
