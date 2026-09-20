<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlfa8cbym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rlfa8cbym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:compass2-filled" {...props}></Icon>
