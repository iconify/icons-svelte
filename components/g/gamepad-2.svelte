<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm8pl7bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm8pl7bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:gamepad-2" {...props}></Icon>
