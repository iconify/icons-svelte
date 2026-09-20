<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9w3e2bqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z9w3e2bqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gamepad-buttons" {...props}></Icon>
