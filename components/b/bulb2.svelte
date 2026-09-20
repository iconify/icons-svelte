<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wokaczbbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wokaczbbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:bulb2" {...props}></Icon>
