<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d407x4otp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="d407x4otp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:globe" {...props}></Icon>
