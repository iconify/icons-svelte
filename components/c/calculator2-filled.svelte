<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy3f9p5rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xy3f9p5rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:calculator2-filled" {...props}></Icon>
