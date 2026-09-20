<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ky01pldxk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ky01pldxk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-sms-block-1" {...props}></Icon>
