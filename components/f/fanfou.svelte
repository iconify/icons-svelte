<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdg6ipbwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdg6ipbwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fanfou" {...props}></Icon>
