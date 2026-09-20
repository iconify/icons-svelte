<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqqf0usjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mqqf0usjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:chandelier-filled" {...props}></Icon>
