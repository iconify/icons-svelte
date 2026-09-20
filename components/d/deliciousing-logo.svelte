<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp8w1geor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pp8w1geor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:deliciousing-logo" {...props}></Icon>
