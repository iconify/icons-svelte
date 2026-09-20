<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t_eq3mbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t_eq3mbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:camera-add2" {...props}></Icon>
