<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jowrko3lu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jowrko3lu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:rest-time-line" {...props}></Icon>
