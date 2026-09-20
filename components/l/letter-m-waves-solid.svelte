<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrkhkpb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrkhkpb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:letter-m-waves-solid" {...props}></Icon>
