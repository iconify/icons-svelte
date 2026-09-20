<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v56jcj3_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-2};
const content = `<path class="v56jcj3_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:joystick-f" {...props}></Icon>
