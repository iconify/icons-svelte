<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9m4xxnfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t9m4xxnfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:locate-round" {...props}></Icon>
