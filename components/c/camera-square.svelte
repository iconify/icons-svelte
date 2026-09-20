<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_f4aibym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y_f4aibym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera-square" {...props}></Icon>
