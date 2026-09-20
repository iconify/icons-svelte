<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clwgi5s7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clwgi5s7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:decentraland" {...props}></Icon>
