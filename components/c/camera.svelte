<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0-8-5b4b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v0-8-5b4b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:camera" {...props}></Icon>
