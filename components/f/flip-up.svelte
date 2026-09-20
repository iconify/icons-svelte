<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ib7m0zbcn.css';
import '../../css/e/ec2kgw3ko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ib7m0zbcn"/><path class="ec2kgw3ko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:flip-up" {...props}></Icon>
